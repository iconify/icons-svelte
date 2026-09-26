<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-3rifbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y-3rifbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-bottom-outline" {...props}></Icon>
