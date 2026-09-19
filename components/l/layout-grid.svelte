<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntw0kh4xh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntw0kh4xh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:layout-grid" {...props}></Icon>
