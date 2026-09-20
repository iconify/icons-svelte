<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp48ishqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jp48ishqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:module-three" {...props}></Icon>
