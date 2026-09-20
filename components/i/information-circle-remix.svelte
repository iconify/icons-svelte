<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g561d8b7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="g561d8b7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:information-circle-remix" {...props}></Icon>
