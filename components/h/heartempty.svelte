<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpjoh6btf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":668};
const content = `<path class="zpjoh6btf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:heartempty" {...props}></Icon>
