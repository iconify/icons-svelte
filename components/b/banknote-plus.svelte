<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7st83bnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7st83bnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:banknote-plus" {...props}></Icon>
