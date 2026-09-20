<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7q918bhw.css';
import '../../css/q/qmjk3ab0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7q918bhw"/><path class="qmjk3ab0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:more-1-line" {...props}></Icon>
