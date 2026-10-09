<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2neunb3u.css';
import '../../css/v/vb5radceb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n2neunb3u"/><path class="vb5radceb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ban-48-bold" {...props}></Icon>
