<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9vd6ubqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9vd6ubqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:latex" {...props}></Icon>
