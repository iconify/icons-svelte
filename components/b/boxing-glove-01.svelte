<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htiu52b-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htiu52b-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:boxing-glove-01" {...props}></Icon>
