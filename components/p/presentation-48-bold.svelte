<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cze6f6b6k.css';
import '../../css/u/un6m0jq1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cze6f6b6k"/><path class="un6m0jq1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:presentation-48-bold" {...props}></Icon>
