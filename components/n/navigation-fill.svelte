<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvf9z4y7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvf9z4y7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:navigation-fill" {...props}></Icon>
