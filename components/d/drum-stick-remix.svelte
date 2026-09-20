<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivvebjbqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ivvebjbqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:drum-stick-remix" {...props}></Icon>
