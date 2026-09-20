<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m42sphumz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m42sphumz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:fill-color-filled" {...props}></Icon>
