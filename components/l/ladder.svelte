<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eswu5sbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eswu5sbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ladder" {...props}></Icon>
