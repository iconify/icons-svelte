<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkwg2476l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkwg2476l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cloud-sun-rain" {...props}></Icon>
