<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgk9rozzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgk9rozzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:layout" {...props}></Icon>
