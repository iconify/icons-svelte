<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh30nu03q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dh30nu03q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chicken-leg" {...props}></Icon>
