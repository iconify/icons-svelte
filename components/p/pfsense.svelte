<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx0db3bno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx0db3bno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pfsense" {...props}></Icon>
