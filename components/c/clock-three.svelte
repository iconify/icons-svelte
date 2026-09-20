<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr-m-zbas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yr-m-zbas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:clock-three" {...props}></Icon>
