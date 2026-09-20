<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mujznmb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mujznmb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:logout2" {...props}></Icon>
