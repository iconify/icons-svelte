<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovp7b9bxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovp7b9bxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rotate-to-horizontal-fill" {...props}></Icon>
