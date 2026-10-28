<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2b73tr4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2b73tr4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-down-a-z" {...props}></Icon>
