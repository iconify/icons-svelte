<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi91kyoxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="yi91kyoxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:paint-bucket-solid" {...props}></Icon>
