<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skioa6b4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="skioa6b4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:drupal-light" {...props}></Icon>
