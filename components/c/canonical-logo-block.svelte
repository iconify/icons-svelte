<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2j98ebkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z2j98ebkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:canonical-logo-block" {...props}></Icon>
