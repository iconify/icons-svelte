<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebwj31uru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ebwj31uru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:ball" {...props}></Icon>
