<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlxe_2blb.css';
import '../../css/v/viv7oac8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dlxe_2blb"/><path class="viv7oac8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:credit-card-insert" {...props}></Icon>
