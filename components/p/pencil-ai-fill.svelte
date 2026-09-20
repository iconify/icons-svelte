<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrtq4obqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrtq4obqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pencil-ai-fill" {...props}></Icon>
