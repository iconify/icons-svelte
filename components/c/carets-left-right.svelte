<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzp8159sj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzp8159sj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:carets-left-right" {...props}></Icon>
