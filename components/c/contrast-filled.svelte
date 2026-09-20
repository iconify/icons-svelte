<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkw_-pbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pkw_-pbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:contrast-filled" {...props}></Icon>
