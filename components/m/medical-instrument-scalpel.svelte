<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7vq9cttl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7vq9cttl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:medical-instrument-scalpel" {...props}></Icon>
