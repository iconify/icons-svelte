<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksbafabbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksbafabbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dice-d4-outline" {...props}></Icon>
