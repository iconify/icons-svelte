<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awwetebdu.css';
import '../../css/p/pyttu4r7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="awwetebdu"/><path clip-rule="evenodd" class="pyttu4r7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:nixos" {...props}></Icon>
