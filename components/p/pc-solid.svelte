<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-7h8fb2z.css';
import '../../css/c/cega53b8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-7h8fb2z"/><path class="cega53b8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:pc-solid" {...props}></Icon>
