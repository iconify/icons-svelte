<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5h4oig5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g5h4oig5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:notification-alarm-snooze-remix" {...props}></Icon>
