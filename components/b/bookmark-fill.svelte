<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqys8njih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqys8njih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:bookmark-fill" {...props}></Icon>
