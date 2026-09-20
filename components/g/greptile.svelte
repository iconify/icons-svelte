<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfkt53w_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wfkt53w_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:greptile" {...props}></Icon>
