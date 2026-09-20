<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz7y-ibfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iz7y-ibfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:png" {...props}></Icon>
