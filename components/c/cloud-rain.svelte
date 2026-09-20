<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezso3g27z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezso3g27z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:cloud-rain" {...props}></Icon>
