<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_30szf3s.css';
import '../../css/m/myoip7bjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_30szf3s"/><path class="myoip7bjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:message-alt-error" {...props}></Icon>
