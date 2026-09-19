<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q17vvwwce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="q17vvwwce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:credit-card" {...props}></Icon>
