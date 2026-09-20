<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw8r3fbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dw8r3fbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kia" {...props}></Icon>
