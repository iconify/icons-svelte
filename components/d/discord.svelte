<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzzpj9b5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pzzpj9b5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:discord" {...props}></Icon>
