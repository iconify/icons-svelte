<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdapskboz.css';
import '../../css/c/cggoknbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdapskboz"/><path class="cggoknbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:alarm-snooze" {...props}></Icon>
