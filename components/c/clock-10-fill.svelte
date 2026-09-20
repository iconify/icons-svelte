<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_q4bebzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w_q4bebzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-10-fill" {...props}></Icon>
