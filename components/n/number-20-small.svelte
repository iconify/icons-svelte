<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxwq0k3ap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxwq0k3ap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-20-small" {...props}></Icon>
