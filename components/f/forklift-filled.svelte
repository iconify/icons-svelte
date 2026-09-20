<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvn751v_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvn751v_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:forklift-filled" {...props}></Icon>
