<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njyl-vsgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njyl-vsgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-group-classic-hung-4-alt" {...props}></Icon>
