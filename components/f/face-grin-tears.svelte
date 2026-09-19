<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqwcfqb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="eqwcfqb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:face-grin-tears" {...props}></Icon>
