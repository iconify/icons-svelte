<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbru0zywf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbru0zywf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:briefcase" {...props}></Icon>
