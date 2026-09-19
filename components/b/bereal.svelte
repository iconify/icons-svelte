<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh_b-1uye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qh_b-1uye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bereal" {...props}></Icon>
