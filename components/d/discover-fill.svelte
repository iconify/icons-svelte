<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_72vybmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r_72vybmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:discover-fill" {...props}></Icon>
