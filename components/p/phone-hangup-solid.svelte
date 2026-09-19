<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy02c7b9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sy02c7b9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:phone-hangup-solid" {...props}></Icon>
