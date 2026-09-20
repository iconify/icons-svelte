<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6s896bnq.css';
import '../../css/b/bur656b8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z6s896bnq"/><path class="bur656b8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:button-solid" {...props}></Icon>
