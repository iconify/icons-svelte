<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq2axpyjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jq2axpyjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:box-filled" {...props}></Icon>
