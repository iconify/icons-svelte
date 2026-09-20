<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpunj9qsv.css';
import '../../css/d/dzeier91r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vpunj9qsv"/><path clip-rule="evenodd" class="dzeier91r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:book-solid" {...props}></Icon>
