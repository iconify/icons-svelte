<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egt7e-0qv.css';
import '../../css/z/z2q2hdbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="egt7e-0qv"/><path class="z2q2hdbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:column-delete" {...props}></Icon>
