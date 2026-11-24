<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz7xlfb-v.css';
import '../../css/b/bbq8uabvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nz7xlfb-v"/><path class="bbq8uabvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:database-zap-filled" {...props}></Icon>
