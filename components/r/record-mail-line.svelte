<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g60q9ts9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g60q9ts9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:record-mail-line" {...props}></Icon>
