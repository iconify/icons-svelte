<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uae56bb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uae56bb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:loop-outline" {...props}></Icon>
