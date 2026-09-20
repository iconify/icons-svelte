<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzcczbrsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tzcczbrsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:code-climate-logo-solid" {...props}></Icon>
