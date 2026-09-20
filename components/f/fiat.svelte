<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7hiw0duv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7hiw0duv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:fiat" {...props}></Icon>
