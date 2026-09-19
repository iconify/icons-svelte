<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7xptq_1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7xptq_1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:arrow-right-fill" {...props}></Icon>
