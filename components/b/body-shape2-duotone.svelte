<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v35r45b_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v35r45b_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:body-shape2-duotone" {...props}></Icon>
