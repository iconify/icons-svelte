<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnn6g-38f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnn6g-38f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:house-lightning-bolt-outline" {...props}></Icon>
