<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg7lrzbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jg7lrzbla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:alarm-clock-plus" {...props}></Icon>
