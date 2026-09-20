<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so3tt3b9a.css';
import '../../css/y/yk8mxxbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="so3tt3b9a"/><path class="yk8mxxbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frappe-gameplan" {...props}></Icon>
