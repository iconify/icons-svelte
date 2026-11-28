<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc2grzw5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tc2grzw5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:expand-solid" {...props}></Icon>
