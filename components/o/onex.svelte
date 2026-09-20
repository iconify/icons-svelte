<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5pwsvboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1545,"height":1151};
const content = `<path class="o5pwsvboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:onex" {...props}></Icon>
