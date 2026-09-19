<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5ds6_93y.css';
import '../../css/f/fkgg8p-2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5ds6_93y"/><path class="fkgg8p-2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:print" {...props}></Icon>
