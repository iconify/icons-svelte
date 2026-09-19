<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddvgu8bvv.css';
import '../../css/h/h8w7ikqqs.css';
import '../../css/s/s8bhpdt9z.css';
import '../../css/c/c4ajp03ul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ddvgu8bvv"><path class="h8w7ikqqs"/><path class="s8bhpdt9z"/><path class="c4ajp03ul"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:inspect-code" {...props}></Icon>
