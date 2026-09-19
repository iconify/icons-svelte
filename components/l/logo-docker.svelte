<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lani2cc-y.css';
import '../../css/m/maksvyb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lani2cc-y"/><path class="maksvyb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-docker" {...props}></Icon>
