<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd8l7tbyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hd8l7tbyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:bigbasket" {...props}></Icon>
