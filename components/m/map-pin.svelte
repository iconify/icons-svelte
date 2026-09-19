<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2htj5fzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q2htj5fzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:map-pin" {...props}></Icon>
