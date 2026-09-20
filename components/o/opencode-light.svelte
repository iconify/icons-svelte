<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti6n5-brp.css';
import '../../css/x/xlhg_tibn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g transform="matrix(1.5 0 0 1.5 -23.858 -7.25)"><path class="ti6n5-brp"/><rect class="xlhg_tibn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:opencode-light" {...props}></Icon>
