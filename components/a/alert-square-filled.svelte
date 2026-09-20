<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na5e8db9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="na5e8db9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:alert-square-filled" {...props}></Icon>
