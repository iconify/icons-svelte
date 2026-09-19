<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/w/w-apjqbzx.css';
import '../../css/r/riw4vyu4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="w-apjqbzx"/><path class="riw4vyu4k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:camera-outline" {...props}></Icon>
