<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk09y49yr.css';
import '../../css/y/yvlpmubcp.css';
import '../../css/b/bw4bmeb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kk09y49yr"/><path clip-rule="evenodd" class="yvlpmubcp"/><path class="bw4bmeb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:gamepad-joystick-right-16" {...props}></Icon>
