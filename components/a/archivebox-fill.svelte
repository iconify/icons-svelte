<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp-z0dg_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="xp-z0dg_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:archivebox-fill" {...props}></Icon>
