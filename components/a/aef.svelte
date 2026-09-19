<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwqbt-xqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mwqbt-xqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:aef" {...props}></Icon>
