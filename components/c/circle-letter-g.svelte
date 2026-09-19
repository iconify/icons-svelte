<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm5s8mbbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fm5s8mbbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-letter-g" {...props}></Icon>
