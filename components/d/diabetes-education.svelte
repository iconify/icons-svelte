<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_m6i_b2e.css';
import '../../css/x/x0zc1fb2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="n_m6i_b2e"/><path class="x0zc1fb2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:diabetes-education" {...props}></Icon>
