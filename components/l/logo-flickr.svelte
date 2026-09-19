<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx39xbeov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fx39xbeov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-flickr" {...props}></Icon>
