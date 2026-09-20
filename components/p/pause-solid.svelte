<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vykw15lgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vykw15lgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:pause-solid" {...props}></Icon>
