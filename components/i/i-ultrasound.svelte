<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g98dd5zxh.css';
import '../../css/e/evjd1k6-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="g98dd5zxh"/><path class="evjd1k6-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-ultrasound" {...props}></Icon>
