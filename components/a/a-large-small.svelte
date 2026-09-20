<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/culuw3unm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="culuw3unm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:a-large-small" {...props}></Icon>
