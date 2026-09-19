<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phvuqczaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phvuqczaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:folder-remove-bold" {...props}></Icon>
