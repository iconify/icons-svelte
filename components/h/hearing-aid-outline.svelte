<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-ooy-buy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b-ooy-buy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:hearing-aid-outline" {...props}></Icon>
