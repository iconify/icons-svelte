<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm6bidcwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xm6bidcwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:drum-fill" {...props}></Icon>
