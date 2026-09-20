<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz-kgxbko.css';
import '../../css/b/bjzxtacce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pz-kgxbko"/><path class="bjzxtacce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:filegator-dark" {...props}></Icon>
