<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jof5-jbvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jof5-jbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:microsoft-yammer-logo-1-block" {...props}></Icon>
