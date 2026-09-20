<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjxwheahl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zjxwheahl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:adobe-photoshop-logo-solid" {...props}></Icon>
