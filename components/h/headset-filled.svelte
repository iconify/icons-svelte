<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-qpzrb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-qpzrb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:headset-filled" {...props}></Icon>
