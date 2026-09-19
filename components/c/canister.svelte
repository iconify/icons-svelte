<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbqt8vb3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="gbqt8vb3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:canister" {...props}></Icon>
