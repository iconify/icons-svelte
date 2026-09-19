<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tesji1z-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="tesji1z-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:drupal" {...props}></Icon>
