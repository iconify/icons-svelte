<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrw7sibnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrw7sibnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-size-select-small" {...props}></Icon>
