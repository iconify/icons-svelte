<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbt_19gof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbt_19gof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-shield-2-fill" {...props}></Icon>
