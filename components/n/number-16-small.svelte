<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyiyvlb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyiyvlb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-16-small" {...props}></Icon>
