<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn5ie-bfc.css';
import '../../css/y/y1lscctme.css';
import '../../css/p/pm4oodhmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":13,"height":24};
const content = `<path class="bn5ie-bfc"/><path class="y1lscctme"/><path class="pm4oodhmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:dna" {...props}></Icon>
