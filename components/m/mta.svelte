<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uym1rkb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uym1rkb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mta" {...props}></Icon>
