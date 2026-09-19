<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3xs06bzl.css';
import '../../css/b/b1v-7vnuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3xs06bzl"/><path class="b1v-7vnuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-buildings" {...props}></Icon>
