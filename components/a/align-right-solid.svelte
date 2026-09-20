<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eiufp5bvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="eiufp5bvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:align-right-solid" {...props}></Icon>
