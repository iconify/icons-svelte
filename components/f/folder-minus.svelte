<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivlssacxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivlssacxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:folder-minus" {...props}></Icon>
