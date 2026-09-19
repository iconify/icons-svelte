<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci9od1bnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ci9od1bnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:alert2x-outline" {...props}></Icon>
