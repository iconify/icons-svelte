<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwci-tmql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwci-tmql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:menu-alt-1" {...props}></Icon>
