<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8zk9jbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="v8zk9jbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:caret-left" {...props}></Icon>
