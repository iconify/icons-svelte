<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgaxh98rp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgaxh98rp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-align-middle" {...props}></Icon>
