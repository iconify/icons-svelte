<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x18z7kh9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":961,"height":1025};
const content = `<path class="x18z7kh9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:paperclip" {...props}></Icon>
