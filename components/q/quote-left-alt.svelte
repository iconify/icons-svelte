<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf-51cbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sf-51cbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:quote-left-alt" {...props}></Icon>
