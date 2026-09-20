<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq49l7bvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vq49l7bvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:basecamp-logo-2-solid" {...props}></Icon>
