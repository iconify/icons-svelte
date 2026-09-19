<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_q1tgnww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r_q1tgnww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:cloud-yes-fill" {...props}></Icon>
