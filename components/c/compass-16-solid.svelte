<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2ln8hpzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d2ln8hpzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:compass-16-solid" {...props}></Icon>
