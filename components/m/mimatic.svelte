<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9abw714l.css';
import '../../css/o/oulxfua7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9abw714l"/><path clip-rule="evenodd" class="oulxfua7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mimatic" {...props}></Icon>
