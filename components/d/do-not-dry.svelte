<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cua6mti1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":520,"height":512};
const content = `<path class="cua6mti1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:do-not-dry" {...props}></Icon>
