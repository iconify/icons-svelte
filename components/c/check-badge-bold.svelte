<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcdvrtlrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcdvrtlrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:check-badge-bold" {...props}></Icon>
