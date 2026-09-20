<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5-aew83i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j5-aew83i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:menu-dots-square-bold" {...props}></Icon>
