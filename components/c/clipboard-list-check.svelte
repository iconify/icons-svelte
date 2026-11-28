<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx1b5ql4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx1b5ql4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:clipboard-list-check" {...props}></Icon>
