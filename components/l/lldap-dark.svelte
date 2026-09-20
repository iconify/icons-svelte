<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa9ce_1pp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xa9ce_1pp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lldap-dark" {...props}></Icon>
