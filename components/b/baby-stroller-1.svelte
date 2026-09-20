<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-jig1b9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-jig1b9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:baby-stroller-1" {...props}></Icon>
