<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnwf6cc6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnwf6cc6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:cpu" {...props}></Icon>
