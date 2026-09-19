<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le8ab_e8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="le8ab_e8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:menu-alt-2" {...props}></Icon>
