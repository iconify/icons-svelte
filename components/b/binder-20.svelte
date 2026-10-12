<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx89adb5k.css';
import '../../css/k/ktkk4-3nx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bx89adb5k"/><path class="ktkk4-3nx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:binder-20" {...props}></Icon>
