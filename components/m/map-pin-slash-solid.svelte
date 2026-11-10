<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie3zn7bfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ie3zn7bfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:map-pin-slash-solid" {...props}></Icon>
