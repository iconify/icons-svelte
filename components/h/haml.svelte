<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx0qcbuxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":300};
const content = `<path class="kx0qcbuxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:haml" {...props}></Icon>
