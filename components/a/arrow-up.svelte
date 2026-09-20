<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8w5lx5ml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8w5lx5ml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:arrow-up" {...props}></Icon>
