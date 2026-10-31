<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adszbn4wz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adszbn4wz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:first-aid-round" {...props}></Icon>
