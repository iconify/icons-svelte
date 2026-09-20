<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3dtuh8zy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3dtuh8zy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:refresh-cw-fill" {...props}></Icon>
