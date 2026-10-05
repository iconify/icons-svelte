<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/f/f4-hall_c.css';
import '../../css/a/a2yusv--h.css';
import '../../css/e/exydi1bdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="f4-hall_c"/><path class="a2yusv--h"/><path class="exydi1bdu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:eye" {...props}></Icon>
