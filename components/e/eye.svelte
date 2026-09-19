<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb4ssgb7r.css';
import '../../css/e/eopyr_bvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="cb4ssgb7r"/><circle class="eopyr_bvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:eye" {...props}></Icon>
