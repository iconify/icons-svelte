<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4qlvzbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="b4qlvzbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:list-ordered-solid" {...props}></Icon>
