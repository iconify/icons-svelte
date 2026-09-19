<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpkt9abpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpkt9abpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:heart" {...props}></Icon>
