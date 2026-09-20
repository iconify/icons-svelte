<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bttz41b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bttz41b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:plus" {...props}></Icon>
