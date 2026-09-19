<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebu-7egqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebu-7egqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:book-open-check" {...props}></Icon>
