<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0-dfyl4d.css';
import '../../css/b/bbqv1obqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f0-dfyl4d"/><path class="bbqv1obqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dam-20" {...props}></Icon>
