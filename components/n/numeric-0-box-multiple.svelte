<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3ctc8bln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3ctc8bln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-0-box-multiple" {...props}></Icon>
