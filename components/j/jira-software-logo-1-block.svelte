<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt3s2tbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vt3s2tbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:jira-software-logo-1-block" {...props}></Icon>
