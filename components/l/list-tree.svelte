<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv595n8kg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv595n8kg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:list-tree" {...props}></Icon>
