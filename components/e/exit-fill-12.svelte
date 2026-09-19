<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1-74yk_y.css';
import '../../css/u/uf53hcsyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="x1-74yk_y"/><path class="uf53hcsyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:exit-fill-12" {...props}></Icon>
