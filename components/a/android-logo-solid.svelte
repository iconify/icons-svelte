<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkpmi-kbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lkpmi-kbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:android-logo-solid" {...props}></Icon>
