<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqd4v7b6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqd4v7b6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-sub-left-down" {...props}></Icon>
