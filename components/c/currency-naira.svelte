<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhuff7bhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhuff7bhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:currency-naira" {...props}></Icon>
