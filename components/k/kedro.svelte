<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho99joejz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ho99joejz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kedro" {...props}></Icon>
