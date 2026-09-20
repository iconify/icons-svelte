<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsjj6nxig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gsjj6nxig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:calculator-alt" {...props}></Icon>
