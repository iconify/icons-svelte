<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/q/q7nwfvbkq.css';
import '../../css/d/dkwns0boj.css';
import '../../css/g/geuvczi2n.css';
import '../../css/b/b43m768zs.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG97xz0cWz"><g class="v3_i3wktz"><path class="q7nwfvbkq"/><path class="dkwns0boj"/><path class="geuvczi2n"/><path class="b43m768zs"/></g></mask></defs><path mask="url(#SVG97xz0cWz)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:handheld" {...props}></Icon>
