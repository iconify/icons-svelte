<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjm_zmoxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hjm_zmoxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:addcomment" {...props}></Icon>
