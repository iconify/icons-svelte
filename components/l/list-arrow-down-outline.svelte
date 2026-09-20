<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd-x80xmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nd-x80xmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-arrow-down-outline" {...props}></Icon>
