<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk_3vtbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jk_3vtbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lldap-light" {...props}></Icon>
