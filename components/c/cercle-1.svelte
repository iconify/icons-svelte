<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4zsyv-to.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n4zsyv-to"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:cercle-1" {...props}></Icon>
