<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re0n-jb1b.css';
import '../../css/g/g55m-ob4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="re0n-jb1b"/><path class="g55m-ob4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ppa-20" {...props}></Icon>
