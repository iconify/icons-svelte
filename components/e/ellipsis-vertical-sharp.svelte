<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7d-ndb_c.css';
import '../../css/n/nulljp8ek.css';
import '../../css/a/a3p68ebjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="q7d-ndb_c"/><circle class="nulljp8ek"/><circle class="a3p68ebjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:ellipsis-vertical-sharp" {...props}></Icon>
