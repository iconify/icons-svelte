<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltt_9pbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ltt_9pbkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:drupal" {...props}></Icon>
