<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-lu_kd2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q-lu_kd2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:delivery-time" {...props}></Icon>
