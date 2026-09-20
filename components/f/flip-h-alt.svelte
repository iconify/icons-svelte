<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_ui0ob4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_ui0ob4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:flip-h-alt" {...props}></Icon>
