<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzfgztf5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzfgztf5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-circle-dots-2-filled" {...props}></Icon>
