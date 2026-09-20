<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz_z0jb7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":168};
const content = `<path class="dz_z0jb7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nuxt" {...props}></Icon>
