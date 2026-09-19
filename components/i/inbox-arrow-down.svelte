<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5bsa5vjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5bsa5vjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:inbox-arrow-down" {...props}></Icon>
