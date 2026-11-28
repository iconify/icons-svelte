<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubdmll87o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubdmll87o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:barcode" {...props}></Icon>
