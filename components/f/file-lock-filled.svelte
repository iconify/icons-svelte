<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-6iqnczv.css';
import '../../css/l/lam0m8b9d.css';
import '../../css/y/yyu6w0k1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u-6iqnczv"/><path class="lam0m8b9d"/><path class="yyu6w0k1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-lock-filled" {...props}></Icon>
