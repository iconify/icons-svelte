<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w01dflzvf.css';
import '../../css/y/y5lz0kbah.css';
import '../../css/m/mv7ibobfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w01dflzvf"/><path class="y5lz0kbah"/><path class="mv7ibobfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-line-dots-20-bold" {...props}></Icon>
