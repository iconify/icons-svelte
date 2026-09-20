<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwk_lb6to.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwk_lb6to"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cvp" {...props}></Icon>
