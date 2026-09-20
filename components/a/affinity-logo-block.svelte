<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4heccbml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e4heccbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:affinity-logo-block" {...props}></Icon>
