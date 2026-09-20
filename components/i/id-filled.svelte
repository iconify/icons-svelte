<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssc1-xone.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ssc1-xone"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:id-filled" {...props}></Icon>
