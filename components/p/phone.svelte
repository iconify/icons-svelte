<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqyhzd34c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqyhzd34c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:phone" {...props}></Icon>
