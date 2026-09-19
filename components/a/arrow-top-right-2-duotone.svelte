<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba_94wemm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ba_94wemm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-top-right-2-duotone" {...props}></Icon>
