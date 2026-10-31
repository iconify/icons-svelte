<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmibc4bxr.css';
import '../../css/m/m90b07a8p.css';
import '../../css/j/jm4p79bio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="nmibc4bxr"/><path class="m90b07a8p"/><path class="jm4p79bio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:georgia" {...props}></Icon>
