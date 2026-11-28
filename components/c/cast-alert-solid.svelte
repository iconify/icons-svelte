<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g748p1bbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g748p1bbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cast-alert-solid" {...props}></Icon>
