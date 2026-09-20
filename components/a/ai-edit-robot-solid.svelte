<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r575v9bcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="r575v9bcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:ai-edit-robot-solid" {...props}></Icon>
