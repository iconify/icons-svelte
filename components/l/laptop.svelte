<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce99elbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ce99elbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:laptop" {...props}></Icon>
