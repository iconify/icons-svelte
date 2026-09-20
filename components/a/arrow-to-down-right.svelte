<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_5qqfbcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j_5qqfbcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-to-down-right" {...props}></Icon>
