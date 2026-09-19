<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-6sj7bos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c-6sj7bos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:four" {...props}></Icon>
