<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djrforfsc.css';
import '../../css/l/lylrjtb6a.css';
import '../../css/a/ak97f6bnh.css';
import '../../css/o/opwr92bel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djrforfsc wm-a"/><path class="lylrjtb6a wm-k"/><path class="ak97f6bnh wm-k"/><path class="opwr92bel wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:binoculars" {...props}></Icon>
