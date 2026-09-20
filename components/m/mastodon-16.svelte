<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsallabfa.css';
import '../../css/h/hc04_ac_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xsallabfa"/><path clip-rule="evenodd" class="hc04_ac_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:mastodon-16" {...props}></Icon>
