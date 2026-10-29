<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jca4lnd7d.css';
import '../../css/m/mwsfceayy.css';
import '../../css/g/gh-chmbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jca4lnd7d wm-k"/><path class="mwsfceayy wm-k"/><path class="gh-chmbev wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:file-audio" {...props}></Icon>
