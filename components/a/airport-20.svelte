<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulf186bsh.css';
import '../../css/a/adm80pb1z.css';
import '../../css/f/f958kxxgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ulf186bsh"/><path class="adm80pb1z"/><path class="f958kxxgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:airport-20" {...props}></Icon>
