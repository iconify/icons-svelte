<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5fs8vb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l5fs8vb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:map-arrow-left" {...props}></Icon>
