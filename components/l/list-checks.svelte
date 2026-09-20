<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k78xrebun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k78xrebun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:list-checks" {...props}></Icon>
