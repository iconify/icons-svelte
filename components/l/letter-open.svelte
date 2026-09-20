<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/n/nw9z_9bah.css';
import '../../css/d/d801rwncm.css';
import '../../css/w/w8wji3bbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="nw9z_9bah"/><path class="d801rwncm"/><path class="w8wji3bbf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:letter-open" {...props}></Icon>
