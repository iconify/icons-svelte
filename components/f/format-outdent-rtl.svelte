<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_l3vcc7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="a_l3vcc7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:format-outdent-rtl" {...props}></Icon>
