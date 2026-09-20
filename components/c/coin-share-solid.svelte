<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhqe0-kgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bhqe0-kgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:coin-share-solid" {...props}></Icon>
