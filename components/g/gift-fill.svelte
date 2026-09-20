<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrt_g7bic.css';
import '../../css/r/rzcm8fagf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zrt_g7bic"/><path class="rzcm8fagf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:gift-fill" {...props}></Icon>
