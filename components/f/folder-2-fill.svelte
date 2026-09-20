<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxopr54xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxopr54xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:folder-2-fill" {...props}></Icon>
