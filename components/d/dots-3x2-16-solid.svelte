<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u08u5qbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u08u5qbww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dots-3x2-16-solid" {...props}></Icon>
