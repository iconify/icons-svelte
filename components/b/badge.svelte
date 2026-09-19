<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9k1kmbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k9k1kmbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:badge" {...props}></Icon>
