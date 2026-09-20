<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5fdn_pim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5fdn_pim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:replace" {...props}></Icon>
