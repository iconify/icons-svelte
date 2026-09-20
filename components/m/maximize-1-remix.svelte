<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1xh9tbwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="s1xh9tbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:maximize-1-remix" {...props}></Icon>
