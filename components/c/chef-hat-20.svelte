<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uczxtfbti.css';
import '../../css/p/p1cx38bqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uczxtfbti"/><path class="p1cx38bqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chef-hat-20" {...props}></Icon>
