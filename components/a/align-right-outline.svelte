<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5j10n4ai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w5j10n4ai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-right-outline" {...props}></Icon>
