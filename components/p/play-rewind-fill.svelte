<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l58myqbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l58myqbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:play-rewind-fill" {...props}></Icon>
