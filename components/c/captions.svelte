<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf4njz2ya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qf4njz2ya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:captions" {...props}></Icon>
