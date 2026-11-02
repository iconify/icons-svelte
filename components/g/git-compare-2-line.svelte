<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txu3124of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txu3124of"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-compare-2-line" {...props}></Icon>
