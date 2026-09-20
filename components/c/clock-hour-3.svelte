<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s89hj8brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s89hj8brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clock-hour-3" {...props}></Icon>
