<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emblogu4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="emblogu4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:arrow-roadmap-solid" {...props}></Icon>
