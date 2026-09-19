<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8oih1dmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p8oih1dmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chevron-left-small" {...props}></Icon>
