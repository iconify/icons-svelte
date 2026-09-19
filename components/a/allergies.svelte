<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv4337xae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rv4337xae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:allergies" {...props}></Icon>
