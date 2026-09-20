<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo1-5g48y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zo1-5g48y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:glasses-bold" {...props}></Icon>
