<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0-dleeea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0-dleeea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:cancel-presentation-line" {...props}></Icon>
