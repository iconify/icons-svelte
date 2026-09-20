<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcb66cb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jcb66cb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:bag-remix" {...props}></Icon>
