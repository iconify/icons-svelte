<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khnqrjkad.css';
import '../../css/u/ukv9p-tgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="khnqrjkad"/><path class="ukv9p-tgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:mongodb-wordmark" {...props}></Icon>
