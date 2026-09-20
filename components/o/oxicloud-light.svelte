<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/den4mekhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="den4mekhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:oxicloud-light" {...props}></Icon>
