<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9jpdwaln.css';
import '../../css/s/s90wc0pdg.css';
import '../../css/t/t2-4x2q-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b9jpdwaln"/><path class="s90wc0pdg"/><path class="t2-4x2q-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:plmail" {...props}></Icon>
