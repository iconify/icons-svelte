<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh1_d4dql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jh1_d4dql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:end-point-solid" {...props}></Icon>
