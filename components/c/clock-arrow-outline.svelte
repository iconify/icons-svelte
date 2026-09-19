<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkci47bpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tkci47bpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:clock-arrow-outline" {...props}></Icon>
