<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv65rtutk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lv65rtutk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:bell-off-outline" {...props}></Icon>
