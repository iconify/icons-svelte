<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5rt3cb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f5rt3cb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:question-outline" {...props}></Icon>
