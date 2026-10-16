<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oddsq5b1n.css';
import '../../css/h/htdwqnb8t.css';
import '../../css/z/z0n64jbsa.css';
import '../../css/d/d19e9sbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oddsq5b1n"/><path class="htdwqnb8t"/><path class="z0n64jbsa"/><path class="d19e9sbid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:export-cable-48" {...props}></Icon>
