<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g83m5gbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g83m5gbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mat-fill" {...props}></Icon>
