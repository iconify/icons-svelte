<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1lv0ib9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1lv0ib9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:cloud" {...props}></Icon>
