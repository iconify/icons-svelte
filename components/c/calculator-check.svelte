<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvv330bbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvv330bbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:calculator-check" {...props}></Icon>
