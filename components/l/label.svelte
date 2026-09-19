<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r71jv83kw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r71jv83kw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:label" {...props}></Icon>
