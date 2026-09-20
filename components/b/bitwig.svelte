<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxbtw5beo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxbtw5beo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bitwig" {...props}></Icon>
