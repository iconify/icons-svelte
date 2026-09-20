<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyau_4blo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyau_4blo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:book-check" {...props}></Icon>
