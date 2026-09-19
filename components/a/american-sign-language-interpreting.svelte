<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x16zck57l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="x16zck57l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:american-sign-language-interpreting" {...props}></Icon>
