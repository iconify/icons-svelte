<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw8gfzvcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sw8gfzvcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:cloud-error-fill" {...props}></Icon>
