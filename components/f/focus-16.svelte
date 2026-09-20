<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwlcgjbwv.css';
import '../../css/d/dngedb3dc.css';
import '../../css/l/lg-e2pb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dwlcgjbwv"/><path clip-rule="evenodd" class="dngedb3dc"/><path class="lg-e2pb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:focus-16" {...props}></Icon>
