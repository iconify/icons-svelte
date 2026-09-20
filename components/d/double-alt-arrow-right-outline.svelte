<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq4vm8b0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sq4vm8b0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:double-alt-arrow-right-outline" {...props}></Icon>
