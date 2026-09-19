<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8yrn8kro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j8yrn8kro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:medication-filled" {...props}></Icon>
