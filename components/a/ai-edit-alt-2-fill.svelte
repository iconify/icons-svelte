<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7gugk-gy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7gugk-gy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-edit-alt-2-fill" {...props}></Icon>
