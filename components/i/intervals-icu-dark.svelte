<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzq2i_09v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":462.9,"height":462.9};
const content = `<path class="yzq2i_09v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:intervals-icu-dark" {...props}></Icon>
