<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylpz7_bpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ylpz7_bpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:radio-minimalistic-outline" {...props}></Icon>
