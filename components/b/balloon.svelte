<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzgxgxc8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzgxgxc8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:balloon" {...props}></Icon>
