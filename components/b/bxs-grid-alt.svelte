<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgjx7bwna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgjx7bwna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-grid-alt" {...props}></Icon>
