<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k82466n8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k82466n8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bug-fill" {...props}></Icon>
