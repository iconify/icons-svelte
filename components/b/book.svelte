<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_v9ndkrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_v9ndkrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:book" {...props}></Icon>
