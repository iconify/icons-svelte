<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2cjcqnme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1084,"height":1074};
const content = `<path class="g2cjcqnme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:accountantos-dark" {...props}></Icon>
