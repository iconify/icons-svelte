<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bskjuj5fc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bskjuj5fc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:mug-hot" {...props}></Icon>
