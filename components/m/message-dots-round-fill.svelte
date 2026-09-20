<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfrkmdbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfrkmdbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:message-dots-round-fill" {...props}></Icon>
