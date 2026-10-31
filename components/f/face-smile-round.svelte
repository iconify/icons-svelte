<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9ln5obuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9ln5obuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:face-smile-round" {...props}></Icon>
