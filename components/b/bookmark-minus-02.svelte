<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3wj9339p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u3wj9339p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bookmark-minus-02" {...props}></Icon>
