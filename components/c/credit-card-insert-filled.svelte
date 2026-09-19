<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux-9n-b3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ux-9n-b3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:credit-card-insert-filled" {...props}></Icon>
