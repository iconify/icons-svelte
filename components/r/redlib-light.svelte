<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd8knp7lm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zd8knp7lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:redlib-light" {...props}></Icon>
