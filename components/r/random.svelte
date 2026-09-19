<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jeswnpbro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":520,"height":472};
const content = `<path class="jeswnpbro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:random" {...props}></Icon>
