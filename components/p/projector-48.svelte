<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjly8-_kl.css';
import '../../css/g/gf8o-_-9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wjly8-_kl"/><path class="gf8o-_-9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:projector-48" {...props}></Icon>
