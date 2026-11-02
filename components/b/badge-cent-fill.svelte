<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd78yzcxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zd78yzcxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:badge-cent-fill" {...props}></Icon>
