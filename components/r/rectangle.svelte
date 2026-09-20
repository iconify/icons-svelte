<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkkdfrb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-4};
const content = `<path class="fkkdfrb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:rectangle" {...props}></Icon>
