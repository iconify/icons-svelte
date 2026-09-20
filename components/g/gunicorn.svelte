<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw3wmisvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gw3wmisvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:gunicorn" {...props}></Icon>
