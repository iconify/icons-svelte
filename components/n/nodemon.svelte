<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xro2qwa6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xro2qwa6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nodemon" {...props}></Icon>
