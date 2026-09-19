<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar01g9bbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="ar01g9bbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:oval-one" {...props}></Icon>
