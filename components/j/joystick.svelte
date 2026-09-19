<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arg7gzb5i.css';
import '../../css/q/quqfatciu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="arg7gzb5i"/><path class="quqfatciu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:joystick" {...props}></Icon>
