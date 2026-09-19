<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4pca5byb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v4pca5byb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ceiling-devere" {...props}></Icon>
