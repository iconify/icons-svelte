<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl9xknbcd.css';
import '../../css/e/euugn8avj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wl9xknbcd"/><path clip-rule="evenodd" class="euugn8avj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:magic-hat-fill" {...props}></Icon>
