<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su_5k-51a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="su_5k-51a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:cloud-alert" {...props}></Icon>
