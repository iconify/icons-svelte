<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oee2xac1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oee2xac1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-parking-solid" {...props}></Icon>
