<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h75wxuipw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h75wxuipw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:font-size" {...props}></Icon>
