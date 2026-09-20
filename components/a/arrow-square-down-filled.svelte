<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah8l-e6gx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ah8l-e6gx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-square-down-filled" {...props}></Icon>
