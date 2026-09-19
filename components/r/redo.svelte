<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pagdp9kcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pagdp9kcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:redo" {...props}></Icon>
