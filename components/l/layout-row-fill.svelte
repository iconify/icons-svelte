<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lctz0c0bf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lctz0c0bf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:layout-row-fill" {...props}></Icon>
