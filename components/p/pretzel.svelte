<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq25kzbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nq25kzbwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pretzel" {...props}></Icon>
