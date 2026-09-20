<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnk1wbbpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bnk1wbbpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:drupal" {...props}></Icon>
