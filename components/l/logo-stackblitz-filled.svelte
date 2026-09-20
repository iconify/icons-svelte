<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf2s_do7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rf2s_do7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-stackblitz-filled" {...props}></Icon>
