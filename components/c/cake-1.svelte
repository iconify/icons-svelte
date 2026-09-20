<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lozn8dbkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lozn8dbkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:cake-1" {...props}></Icon>
