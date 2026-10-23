<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzgb5fb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzgb5fb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:eye-dashed" {...props}></Icon>
