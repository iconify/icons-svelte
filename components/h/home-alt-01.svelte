<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7f1g37vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7f1g37vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:home-alt-01" {...props}></Icon>
