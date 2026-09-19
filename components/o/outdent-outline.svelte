<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx3fmrb6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wx3fmrb6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:outdent-outline" {...props}></Icon>
