<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oup59lb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oup59lb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:arrow-down-filled" {...props}></Icon>
