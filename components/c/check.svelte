<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x15yxzb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x15yxzb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:check" {...props}></Icon>
