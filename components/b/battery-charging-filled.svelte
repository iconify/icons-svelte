<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku9hb1yoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ku9hb1yoa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:battery-charging-filled" {...props}></Icon>
