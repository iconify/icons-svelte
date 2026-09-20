<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmqe0vb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmqe0vb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:laptop" {...props}></Icon>
