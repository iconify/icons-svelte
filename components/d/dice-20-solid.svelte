<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5y2e5btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="u5y2e5btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dice-20-solid" {...props}></Icon>
