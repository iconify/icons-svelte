<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g51-dbv_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g51-dbv_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:life-ring-light" {...props}></Icon>
