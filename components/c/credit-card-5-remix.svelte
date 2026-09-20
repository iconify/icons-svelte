<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-hvrfb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="t-hvrfb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:credit-card-5-remix" {...props}></Icon>
