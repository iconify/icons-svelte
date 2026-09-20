<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rotba7baa.css';
import '../../css/c/c52h3c0el.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rotba7baa"/><path class="c52h3c0el"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-horizonta-spacing-bold-duotone" {...props}></Icon>
