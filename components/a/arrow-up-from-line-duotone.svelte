<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5oyuwx-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary u5oyuwx-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-up-from-line-duotone" {...props}></Icon>
