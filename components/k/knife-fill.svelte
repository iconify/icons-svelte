<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8be_q3jj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8be_q3jj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:knife-fill" {...props}></Icon>
