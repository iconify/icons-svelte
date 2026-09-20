<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvmw99abz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvmw99abz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:refresh-right-square-filled" {...props}></Icon>
