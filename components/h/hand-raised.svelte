<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un7t3abng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="un7t3abng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:hand-raised" {...props}></Icon>
