<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v89uo1arz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v89uo1arz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:briefcase-2-fill" {...props}></Icon>
