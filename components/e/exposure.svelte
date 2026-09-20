<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm95fc3hw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gm95fc3hw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:exposure" {...props}></Icon>
