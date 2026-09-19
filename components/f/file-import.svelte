<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da6e7c_me.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="da6e7c_me"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:file-import" {...props}></Icon>
