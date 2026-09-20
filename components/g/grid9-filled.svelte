<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3cdd9bfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u3cdd9bfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:grid9-filled" {...props}></Icon>
