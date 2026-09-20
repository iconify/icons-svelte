<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbzaf21-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbzaf21-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:anthropic" {...props}></Icon>
