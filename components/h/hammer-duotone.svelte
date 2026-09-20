<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beb4umbqn.css';
import '../../css/o/ol2kopnbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="beb4umbqn"/><path class="ol2kopnbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:hammer-duotone" {...props}></Icon>
