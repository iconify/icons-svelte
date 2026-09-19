<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygd2uvbqw.css';
import '../../css/f/fpb-29h3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ygd2uvbqw"/><path class="fpb-29h3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:cursor" {...props}></Icon>
