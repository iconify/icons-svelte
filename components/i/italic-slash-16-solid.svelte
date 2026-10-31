<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nonchgb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nonchgb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:italic-slash-16-solid" {...props}></Icon>
