<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9r2hdbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k9r2hdbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:notification-filled" {...props}></Icon>
