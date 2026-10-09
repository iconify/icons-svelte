<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u20py2moy.css';
import '../../css/h/hi068jb0r.css';
import '../../css/u/uajmqugut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u20py2moy"/><path class="hi068jb0r"/><path class="uajmqugut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:move-20-bold" {...props}></Icon>
