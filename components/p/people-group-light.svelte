<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpa_lkb0t.css';
import '../../css/z/zdz2_wbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpa_lkb0t"/><path class="zdz2_wbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:people-group-light" {...props}></Icon>
