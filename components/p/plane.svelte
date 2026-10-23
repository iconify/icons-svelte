<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os4_1jwqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="os4_1jwqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:plane" {...props}></Icon>
