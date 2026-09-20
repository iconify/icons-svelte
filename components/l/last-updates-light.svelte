<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmme1dbbu.css';
import '../../css/z/zju01gbvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmme1dbbu"/><path class="zju01gbvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:last-updates-light" {...props}></Icon>
