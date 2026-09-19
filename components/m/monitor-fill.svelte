<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7y4-ubod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7y4-ubod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:monitor-fill" {...props}></Icon>
