<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn9ufwz-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gn9ufwz-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mic" {...props}></Icon>
