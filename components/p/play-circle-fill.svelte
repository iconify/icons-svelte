<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pttofhins.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pttofhins"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:play-circle-fill" {...props}></Icon>
