<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/x/x3z6ypblj.css';
import '../../css/j/jqbgtl3yn.css';
import '../../css/l/lns-4nbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="x3z6ypblj"/><path class="jqbgtl3yn"/><path class="lns-4nbyt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:captions" {...props}></Icon>
