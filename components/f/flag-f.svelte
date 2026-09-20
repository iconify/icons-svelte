<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kevq8pw6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="kevq8pw6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:flag-f" {...props}></Icon>
