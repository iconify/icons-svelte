<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r05ajhrur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r05ajhrur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:abbvie" {...props}></Icon>
