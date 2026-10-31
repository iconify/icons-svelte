<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpfeuxjdz.css';
import '../../css/j/j33ca7bac.css';
import '../../css/e/et9g0gkeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="cpfeuxjdz"/><path class="j33ca7bac"/><path class="et9g0gkeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:nauru" {...props}></Icon>
