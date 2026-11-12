<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv017rgfy.css';
import '../../css/g/gk9fq7bun.css';
import '../../css/a/a0ch81bxw.css';
import '../../css/n/ntier-hqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gv017rgfy"/><path class="gk9fq7bun"/><path class="a0ch81bxw"/><path class="ntier-hqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lidbrainz-light" {...props}></Icon>
