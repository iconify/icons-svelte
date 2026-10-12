<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxlfpzpjb.css';
import '../../css/f/fce5xcc5l.css';
import '../../css/h/hyt904_lx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxlfpzpjb"/><path clip-rule="evenodd" class="fce5xcc5l"/><path class="hyt904_lx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:globe-lock-filled" {...props}></Icon>
