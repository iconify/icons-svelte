<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn0o0fblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qn0o0fblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:award-check" {...props}></Icon>
