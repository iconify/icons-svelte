<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0o93bc9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0o93bc9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:laptop" {...props}></Icon>
