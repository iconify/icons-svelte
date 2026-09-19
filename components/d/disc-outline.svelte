<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w84vznkgo.css';
import '../../css/f/fb3944y_s.css';
import '../../css/a/a1bg4hbvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="w84vznkgo"/><circle class="fb3944y_s"/><circle class="a1bg4hbvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:disc-outline" {...props}></Icon>
