<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwntzwjid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="bwntzwjid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:basket-minus-solid" {...props}></Icon>
