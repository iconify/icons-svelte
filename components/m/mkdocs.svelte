<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej8rvisjq.css';
import '../../css/n/np34t097q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ej8rvisjq"/><path class="np34t097q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mkdocs" {...props}></Icon>
