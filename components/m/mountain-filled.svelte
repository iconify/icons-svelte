<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tky61jwtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tky61jwtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:mountain-filled" {...props}></Icon>
