<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxt1ofkec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":457,"height":680};
const content = `<path class="wxt1ofkec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:italic" {...props}></Icon>
