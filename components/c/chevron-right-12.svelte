<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_ruc1bdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="n_ruc1bdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:chevron-right-12" {...props}></Icon>
