<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqih_6qlj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqih_6qlj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:alarm-slash" {...props}></Icon>
