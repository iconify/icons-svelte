<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvjn01b8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qvjn01b8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ministry-of-health" {...props}></Icon>
