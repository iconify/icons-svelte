<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9t-m7blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9t-m7blb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:rocket-filled" {...props}></Icon>
