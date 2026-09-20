<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn6vufbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sn6vufbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:lock" {...props}></Icon>
