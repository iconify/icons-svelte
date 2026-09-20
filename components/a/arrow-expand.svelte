<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju6kq_tox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ju6kq_tox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:arrow-expand" {...props}></Icon>
