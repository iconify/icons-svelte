<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg9i9abcg.css';
import '../../css/u/u_kzc3htk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="vg9i9abcg"/><path class="u_kzc3htk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-registration" {...props}></Icon>
