<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg-0z5wjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pg-0z5wjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:milestone" {...props}></Icon>
