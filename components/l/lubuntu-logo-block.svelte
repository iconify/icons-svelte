<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpkb6h12s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jpkb6h12s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:lubuntu-logo-block" {...props}></Icon>
