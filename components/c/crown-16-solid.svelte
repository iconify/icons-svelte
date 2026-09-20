<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqosfp8bb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dqosfp8bb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:crown-16-solid" {...props}></Icon>
