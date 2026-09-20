<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grcmtww9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="grcmtww9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:broadcom-logo-solid" {...props}></Icon>
