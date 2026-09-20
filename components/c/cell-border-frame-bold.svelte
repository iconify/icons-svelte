<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z56x6q5sj.css';
import '../../css/q/qwgvg7v0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z56x6q5sj"/><path class="qwgvg7v0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cell-border-frame-bold" {...props}></Icon>
