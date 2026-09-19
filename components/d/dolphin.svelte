<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc-y9fbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="jc-y9fbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:dolphin" {...props}></Icon>
