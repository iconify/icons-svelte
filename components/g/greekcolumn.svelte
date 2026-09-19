<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw-94rbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="kw-94rbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:greekcolumn" {...props}></Icon>
