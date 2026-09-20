<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8bb0e_4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y8bb0e_4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:garage-fill" {...props}></Icon>
