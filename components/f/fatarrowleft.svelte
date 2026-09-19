<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v59xqacos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1025};
const content = `<path class="v59xqacos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:fatarrowleft" {...props}></Icon>
