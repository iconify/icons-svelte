<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po3mlvuua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="po3mlvuua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:easy-redmine-light" {...props}></Icon>
