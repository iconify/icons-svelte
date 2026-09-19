<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/gd8dsqbqp.css';
import '../../css/c/craj1zw4d.css';
import '../../css/g/gqixgnb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="gd8dsqbqp"/><path class="craj1zw4d"/><path class="gqixgnb9o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:calculator-light" {...props}></Icon>
