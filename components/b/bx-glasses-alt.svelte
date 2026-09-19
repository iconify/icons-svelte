<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovau7gmyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovau7gmyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-glasses-alt" {...props}></Icon>
