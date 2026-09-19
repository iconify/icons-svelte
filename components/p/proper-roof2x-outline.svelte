<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy4n6yuzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qy4n6yuzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:proper-roof2x-outline" {...props}></Icon>
