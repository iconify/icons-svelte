<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va9rngbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="va9rngbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:dice-d4-solid" {...props}></Icon>
