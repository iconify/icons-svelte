<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/a/a6nhw7byy.css';
import '../../css/g/gl0peof1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="a6nhw7byy"/><path class="gl0peof1z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:circle-minus" {...props}></Icon>
