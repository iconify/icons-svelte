<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szu0jobmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szu0jobmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:dot-03-m" {...props}></Icon>
