<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzg4qtqlm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzg4qtqlm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:cup-soda" {...props}></Icon>
