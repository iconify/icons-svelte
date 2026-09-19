<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvqwwe6ij.css';
import '../../css/g/guc_2ccot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bvqwwe6ij"/><path class="guc_2ccot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:aion" {...props}></Icon>
