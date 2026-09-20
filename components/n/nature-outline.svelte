<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez0wvl5yk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ez0wvl5yk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:nature-outline" {...props}></Icon>
