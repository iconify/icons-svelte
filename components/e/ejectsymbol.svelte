<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl-50nbno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="yl-50nbno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:ejectsymbol" {...props}></Icon>
