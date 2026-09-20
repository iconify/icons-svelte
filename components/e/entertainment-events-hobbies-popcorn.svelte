<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukm4dob-t.css';
import '../../css/y/yh-c-kbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ukm4dob-t"/><path class="yh-c-kbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:entertainment-events-hobbies-popcorn" {...props}></Icon>
