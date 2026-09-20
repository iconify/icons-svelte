<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz2soiqdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uz2soiqdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:remedy-entertainment" {...props}></Icon>
