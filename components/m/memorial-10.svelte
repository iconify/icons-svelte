<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz7foyb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":10};
const content = `<path class="cz7foyb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:memorial-10" {...props}></Icon>
