<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_3bmbf_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="a_3bmbf_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:horizontal-rule-fill-12" {...props}></Icon>
