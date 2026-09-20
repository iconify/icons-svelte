<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnm57cc3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="lnm57cc3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:bone" {...props}></Icon>
