<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui7t-jbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ui7t-jbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:menu-square" {...props}></Icon>
