<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9e51dbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b9e51dbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:align-selection-solid" {...props}></Icon>
