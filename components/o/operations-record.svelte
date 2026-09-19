<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evzzowain.css';
import '../../css/p/p0vee9bvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="evzzowain"/><path class="p0vee9bvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:operations-record" {...props}></Icon>
