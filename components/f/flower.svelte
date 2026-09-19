<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7d-ndb_c.css';
import '../../css/h/hx4nelfav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="q7d-ndb_c"/><path class="hx4nelfav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:flower" {...props}></Icon>
