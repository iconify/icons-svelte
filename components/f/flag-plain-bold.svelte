<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8umd8lyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d8umd8lyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:flag-plain-bold" {...props}></Icon>
