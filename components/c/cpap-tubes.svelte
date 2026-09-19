<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7b5tjbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="t7b5tjbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:cpap-tubes" {...props}></Icon>
