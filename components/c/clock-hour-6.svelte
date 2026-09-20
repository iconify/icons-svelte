<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbitgnb_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbitgnb_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clock-hour-6" {...props}></Icon>
