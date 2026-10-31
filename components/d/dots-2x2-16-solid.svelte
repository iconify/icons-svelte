<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr9tc44vt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fr9tc44vt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dots-2x2-16-solid" {...props}></Icon>
