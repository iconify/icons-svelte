<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejqveqb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ejqveqb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:gowalla-logo-1-block" {...props}></Icon>
