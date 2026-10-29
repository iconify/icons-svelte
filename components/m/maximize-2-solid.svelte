<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kaq68ebxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kaq68ebxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:maximize-2-solid" {...props}></Icon>
