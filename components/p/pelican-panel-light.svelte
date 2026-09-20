<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgd8wvghw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jgd8wvghw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pelican-panel-light" {...props}></Icon>
