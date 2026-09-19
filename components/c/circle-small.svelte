<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uynuzcb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="uynuzcb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:circle-small" {...props}></Icon>
