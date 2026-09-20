<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt4g3v8ea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mt4g3v8ea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:book-open-duotone-line" {...props}></Icon>
