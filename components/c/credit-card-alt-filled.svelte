<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p55tnhbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p55tnhbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:credit-card-alt-filled" {...props}></Icon>
