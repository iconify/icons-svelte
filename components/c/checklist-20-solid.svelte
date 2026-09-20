<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q27yq5cdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q27yq5cdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:checklist-20-solid" {...props}></Icon>
