<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ariwul1cm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ariwul1cm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:invoice-solid" {...props}></Icon>
