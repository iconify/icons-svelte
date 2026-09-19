<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6ros9nur.css';
import '../../css/c/c8kuy_ape.css';
import '../../css/x/xt_a157cz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i6ros9nur"/><circle class="c8kuy_ape"/><path class="xt_a157cz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:instance-classic" {...props}></Icon>
