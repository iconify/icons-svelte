<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v46z5iboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v46z5iboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:r3" {...props}></Icon>
