<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6x8okbaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a6x8okbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:headphone-fill" {...props}></Icon>
