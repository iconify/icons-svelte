<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-v_mj_8z.css';
import '../../css/v/v4evbjbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-v_mj_8z"/><path class="v4evbjbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:monetize-duotone" {...props}></Icon>
