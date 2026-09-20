<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wunxpj0up.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wunxpj0up"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:forte-dark" {...props}></Icon>
