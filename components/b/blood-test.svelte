<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si5ky56_s.css';
import '../../css/w/w-1mownrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="si5ky56_s"/><path class="w-1mownrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:blood-test" {...props}></Icon>
