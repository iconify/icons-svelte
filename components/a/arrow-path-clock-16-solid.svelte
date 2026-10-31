<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euu_br-wc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="euu_br-wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-path-clock-16-solid" {...props}></Icon>
