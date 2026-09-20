<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq5_84bmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dq5_84bmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:asciinema" {...props}></Icon>
