<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha6_mzzpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ha6_mzzpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bell-filled" {...props}></Icon>
