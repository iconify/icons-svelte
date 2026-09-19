<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v27imyb9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v27imyb9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:diamond-gem-filled" {...props}></Icon>
