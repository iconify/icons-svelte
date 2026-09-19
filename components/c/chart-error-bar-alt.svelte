<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqtyr2w2k.css';
import '../../css/h/hgpzimtyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qqtyr2w2k"/><path class="hgpzimtyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-error-bar-alt" {...props}></Icon>
