<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/v/veml0mbwe.css';
import '../../css/j/j8f4t4bxc.css';
import '../../css/j/jgx7b9k1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="veml0mbwe"/><path class="j8f4t4bxc"/><path class="jgx7b9k1w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:insert-column-left" {...props}></Icon>
