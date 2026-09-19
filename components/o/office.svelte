<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkzo_-i4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkzo_-i4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:office" {...props}></Icon>
