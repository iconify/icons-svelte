<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1cd98tjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1cd98tjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:check-unread-04" {...props}></Icon>
