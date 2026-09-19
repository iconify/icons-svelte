<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnagsebtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnagsebtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:pen-nib-outline" {...props}></Icon>
