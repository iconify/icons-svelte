<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eslal3bkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eslal3bkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:plus-box-outline" {...props}></Icon>
