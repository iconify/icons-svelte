<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej88bgb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ej88bgb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lldap" {...props}></Icon>
