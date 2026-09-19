<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2ca7acla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2ca7acla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:options-2-fill" {...props}></Icon>
