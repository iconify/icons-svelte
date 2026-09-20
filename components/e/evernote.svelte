<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8hg_bbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8hg_bbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:evernote" {...props}></Icon>
