<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pflvn04nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pflvn04nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:csswizardry" {...props}></Icon>
