<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpmf8sb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vpmf8sb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:person" {...props}></Icon>
