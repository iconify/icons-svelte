<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl95zaqil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rl95zaqil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-letter-y" {...props}></Icon>
