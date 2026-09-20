<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uov_89a-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uov_89a-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:compasses-fill" {...props}></Icon>
