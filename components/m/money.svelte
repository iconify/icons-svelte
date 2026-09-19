<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s34_ysbgj.css';
import '../../css/l/l5ntip6-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s34_ysbgj"/><path class="l5ntip6-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:money" {...props}></Icon>
