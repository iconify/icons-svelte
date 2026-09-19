<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqf2av3eh.css';
import '../../css/f/fs-22ozdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kqf2av3eh"/><path class="fs-22ozdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:drink-01" {...props}></Icon>
