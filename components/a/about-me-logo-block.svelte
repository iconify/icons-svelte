<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8buwubvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n8buwubvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:about-me-logo-block" {...props}></Icon>
