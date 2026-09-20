<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axlz7bb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="axlz7bb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:expand-less-fill" {...props}></Icon>
