<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-x2wsljl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="c-x2wsljl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:call-center-support-service-solid" {...props}></Icon>
