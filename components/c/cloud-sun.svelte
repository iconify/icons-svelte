<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h36_77paj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h36_77paj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cloud-sun" {...props}></Icon>
