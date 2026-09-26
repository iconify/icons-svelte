<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7no_4brg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v7no_4brg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-bottom-bold" {...props}></Icon>
