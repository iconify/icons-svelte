<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxhtjnb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wxhtjnb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:animal-chicken" {...props}></Icon>
