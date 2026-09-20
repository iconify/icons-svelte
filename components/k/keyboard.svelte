<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlezn2bhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlezn2bhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:keyboard" {...props}></Icon>
