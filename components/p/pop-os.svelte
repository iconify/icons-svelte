<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-g1w9bxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-g1w9bxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pop-os" {...props}></Icon>
