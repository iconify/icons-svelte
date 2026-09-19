<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6wz8cb3t.css';
import '../../css/e/e12eg19wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="t6wz8cb3t"/><path class="e12eg19wq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:eye-fill" {...props}></Icon>
