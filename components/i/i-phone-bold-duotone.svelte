<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd06o6ovg.css';
import '../../css/u/ur40gui8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dd06o6ovg"/><path class="ur40gui8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:i-phone-bold-duotone" {...props}></Icon>
