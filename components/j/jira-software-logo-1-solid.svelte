<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge6e27bsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ge6e27bsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:jira-software-logo-1-solid" {...props}></Icon>
