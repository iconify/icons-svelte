<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o05od65xh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o05od65xh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:clipboard-outline" {...props}></Icon>
