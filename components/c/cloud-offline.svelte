<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s15jikkii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s15jikkii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:cloud-offline" {...props}></Icon>
