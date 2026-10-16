<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2v02vmol.css';
import '../../css/m/m4hmbobqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y2v02vmol"/><path class="m4hmbobqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:letter-case-20" {...props}></Icon>
