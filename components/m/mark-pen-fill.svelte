<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqhvoz1ft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqhvoz1ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mark-pen-fill" {...props}></Icon>
