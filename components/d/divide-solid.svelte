<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5cg0fb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v5cg0fb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:divide-solid" {...props}></Icon>
