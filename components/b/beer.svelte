<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa0q_wbng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="xa0q_wbng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:beer" {...props}></Icon>
