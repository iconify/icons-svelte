<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi-ue2tqy.css';
import '../../css/m/mo_rg4g7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bi-ue2tqy"/><path class="mo_rg4g7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:prq" {...props}></Icon>
