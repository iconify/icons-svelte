<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpc_a-egz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gpc_a-egz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-mysql" {...props}></Icon>
