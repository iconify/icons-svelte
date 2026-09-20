<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo5-0ek9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lo5-0ek9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-threads" {...props}></Icon>
