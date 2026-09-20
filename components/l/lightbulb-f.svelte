<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_j-4i_al.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-1.5};
const content = `<path class="c_j-4i_al"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:lightbulb-f" {...props}></Icon>
