<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdm1b8b0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdm1b8b0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:equad" {...props}></Icon>
