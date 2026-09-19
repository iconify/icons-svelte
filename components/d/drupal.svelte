<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf5_0tv0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="uf5_0tv0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:drupal" {...props}></Icon>
