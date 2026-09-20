<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0vzk4-mo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i0vzk4-mo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:c-plus-language-logo-block" {...props}></Icon>
