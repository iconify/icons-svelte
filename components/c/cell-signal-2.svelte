<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etx7hfm9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etx7hfm9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cell-signal-2" {...props}></Icon>
