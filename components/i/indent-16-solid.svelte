<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs49-jbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xs49-jbes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:indent-16-solid" {...props}></Icon>
