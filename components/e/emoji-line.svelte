<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-e_8qbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-e_8qbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:emoji-line" {...props}></Icon>
