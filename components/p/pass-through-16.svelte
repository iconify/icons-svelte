<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1t2h770l.css';
import '../../css/n/nbyo3qbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z1t2h770l"/><path class="nbyo3qbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:pass-through-16" {...props}></Icon>
