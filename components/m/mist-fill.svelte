<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxac1nb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxac1nb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mist-fill" {...props}></Icon>
