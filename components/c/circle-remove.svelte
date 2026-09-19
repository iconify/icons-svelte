<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcl5t7bpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="bcl5t7bpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:circle-remove" {...props}></Icon>
