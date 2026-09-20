<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmzsi1y9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmzsi1y9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-checklist-duotone" {...props}></Icon>
