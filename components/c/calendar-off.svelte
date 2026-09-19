<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxd2gpb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lxd2gpb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:calendar-off" {...props}></Icon>
