<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv3vohdsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lv3vohdsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:layout-dashboard-filled" {...props}></Icon>
