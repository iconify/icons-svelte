<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjx9i3gfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tjx9i3gfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:microsoft-azure-logo-block" {...props}></Icon>
