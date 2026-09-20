<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3c01c2if.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3c01c2if"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:chartmogul" {...props}></Icon>
