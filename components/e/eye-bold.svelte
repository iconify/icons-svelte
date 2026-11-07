<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk94-14if.css';
import '../../css/t/tjyrjeb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kk94-14if"/><path clip-rule="evenodd" class="tjyrjeb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:eye-bold" {...props}></Icon>
