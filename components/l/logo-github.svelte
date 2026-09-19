<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqdh2xlzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mqdh2xlzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-github" {...props}></Icon>
