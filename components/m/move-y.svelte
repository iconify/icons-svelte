<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/k/ki8yqbcwf.css';
import '../../css/v/vjbjg0b1y.css';
import '../../css/s/s-6ff4b-x.css';
import '../../css/n/n2651fbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="ki8yqbcwf"/><path class="vjbjg0b1y"/><path class="s-6ff4b-x"/><path class="n2651fbqx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:move-y" {...props}></Icon>
