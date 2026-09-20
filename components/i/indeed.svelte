<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xax_3jbiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xax_3jbiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:indeed" {...props}></Icon>
