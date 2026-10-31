<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl8iuabrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kl8iuabrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:message-square-text-gloss" {...props}></Icon>
