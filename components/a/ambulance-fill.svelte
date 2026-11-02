<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j54l0rc7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j54l0rc7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ambulance-fill" {...props}></Icon>
