<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmh8u_78t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmh8u_78t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:clock-plus" {...props}></Icon>
