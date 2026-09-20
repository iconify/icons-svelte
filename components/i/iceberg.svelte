<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arac17bjm.css';
import '../../css/b/bjy6rwbot.css';
import '../../css/r/rc8gboi9c.css';
import '../../css/m/mfqg_7hka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="arac17bjm"/><path class="bjy6rwbot"/><path class="rc8gboi9c"/><path class="mfqg_7hka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:iceberg" {...props}></Icon>
