<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9y6vm_gf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9y6vm_gf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:expand" {...props}></Icon>
