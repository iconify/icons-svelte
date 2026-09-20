<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc2n97b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sc2n97b4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:grid9" {...props}></Icon>
