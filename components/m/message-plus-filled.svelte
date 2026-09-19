<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc9q8fb3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sc9q8fb3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-plus-filled" {...props}></Icon>
