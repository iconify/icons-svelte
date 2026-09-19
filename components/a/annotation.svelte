<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibd4rs_xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibd4rs_xs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:annotation" {...props}></Icon>
