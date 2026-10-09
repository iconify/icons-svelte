<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su2fj2bbc.css';
import '../../css/k/ksiw30c1e.css';
import '../../css/d/d1u5dmb3x.css';
import '../../css/o/oduy0uyli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="su2fj2bbc"/><path class="ksiw30c1e"/><path class="d1u5dmb3x"/><path class="oduy0uyli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:leaf-plus-20" {...props}></Icon>
