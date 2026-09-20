<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zregm3blr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zregm3blr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:milestone" {...props}></Icon>
