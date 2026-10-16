<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdz6p2bks.css';
import '../../css/c/c8s5nepqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xdz6p2bks"/><path class="c8s5nepqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:respirator-20-bold" {...props}></Icon>
