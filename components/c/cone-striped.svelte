<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nemsf-b9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nemsf-b9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cone-striped" {...props}></Icon>
