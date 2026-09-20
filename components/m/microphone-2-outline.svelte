<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/faxw97p3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="faxw97p3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:microphone-2-outline" {...props}></Icon>
