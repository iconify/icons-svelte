<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju2nyvbsw.css';
import '../../css/a/ac_be7bih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ju2nyvbsw"/><path class="ac_be7bih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:mobile-download" {...props}></Icon>
