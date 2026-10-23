<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apu_4kbns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="apu_4kbns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:heading-3" {...props}></Icon>
