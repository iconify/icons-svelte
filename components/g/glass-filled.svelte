<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moqx-40tt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="moqx-40tt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:glass-filled" {...props}></Icon>
