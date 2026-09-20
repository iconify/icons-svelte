<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz0oc4b4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mz0oc4b4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-3-sharp" {...props}></Icon>
