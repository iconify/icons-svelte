<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyxi0acao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="wyxi0acao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:border-left-right" {...props}></Icon>
