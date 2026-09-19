<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks6dkibpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ks6dkibpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-return-left" {...props}></Icon>
