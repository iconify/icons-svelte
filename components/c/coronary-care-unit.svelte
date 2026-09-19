<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4u0dd6fq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="y4u0dd6fq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:coronary-care-unit" {...props}></Icon>
