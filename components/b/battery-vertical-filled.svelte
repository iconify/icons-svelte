<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykf21lh5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykf21lh5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:battery-vertical-filled" {...props}></Icon>
