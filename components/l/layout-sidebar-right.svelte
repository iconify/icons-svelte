<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqvswxb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqvswxb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-sidebar-right" {...props}></Icon>
