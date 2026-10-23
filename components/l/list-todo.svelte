<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr1-48blm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sr1-48blm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:list-todo" {...props}></Icon>
