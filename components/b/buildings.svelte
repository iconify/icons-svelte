<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3xs06bzl.css';
import '../../css/i/i19gygbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3xs06bzl"/><path class="i19gygbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:buildings" {...props}></Icon>
