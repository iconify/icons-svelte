<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlg_8-b-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nlg_8-b-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:microsoft-teams-logo-block" {...props}></Icon>
