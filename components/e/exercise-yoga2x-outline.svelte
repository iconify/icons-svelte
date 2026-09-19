<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t10i58gej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="t10i58gej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:exercise-yoga2x-outline" {...props}></Icon>
