<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-l-pb8zd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-l-pb8zd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:align-horizontal-center" {...props}></Icon>
