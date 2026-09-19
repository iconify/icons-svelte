<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2hji3bha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z2hji3bha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-card" {...props}></Icon>
