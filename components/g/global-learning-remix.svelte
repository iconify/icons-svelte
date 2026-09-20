<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3kcvrbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="u3kcvrbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:global-learning-remix" {...props}></Icon>
