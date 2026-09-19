<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eykbg7b3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="eykbg7b3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:prestashop" {...props}></Icon>
