<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6ilb7ewq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6ilb7ewq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-number-9-solid" {...props}></Icon>
