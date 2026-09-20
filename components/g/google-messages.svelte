<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvw901bjd.css';
import '../../css/k/k468snbzm.css';
import '../../css/r/rqpbbk94c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gvw901bjd"/><path class="k468snbzm"/><path class="rqpbbk94c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-messages" {...props}></Icon>
