<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/z/zci0-sn6j.css';
import '../../css/n/nuv4bub9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="zci0-sn6j"/><path class="nuv4bub9l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:book" {...props}></Icon>
