<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5s29jsll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5s29jsll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:coin-monero-filled" {...props}></Icon>
