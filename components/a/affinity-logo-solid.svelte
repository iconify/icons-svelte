<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b86j1lb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b86j1lb-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:affinity-logo-solid" {...props}></Icon>
