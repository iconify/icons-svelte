<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqmpb4b4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dqmpb4b4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:medicine-bottle" {...props}></Icon>
