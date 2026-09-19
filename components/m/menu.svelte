<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_emwl_aw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="o_emwl_aw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:menu" {...props}></Icon>
