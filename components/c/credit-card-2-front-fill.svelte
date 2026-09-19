<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqy0fzbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sqy0fzbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:credit-card-2-front-fill" {...props}></Icon>
