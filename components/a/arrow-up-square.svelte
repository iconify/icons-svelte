<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/x/x9ygbfb0o.css';
import '../../css/g/gz5u9l3ok.css';
import '../../css/t/tbfod3hgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="x9ygbfb0o"/><path class="gz5u9l3ok"/><rect class="tbfod3hgq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:arrow-up-square" {...props}></Icon>
