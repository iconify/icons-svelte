<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo9gfy0rz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oo9gfy0rz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:mail-open-solid" {...props}></Icon>
