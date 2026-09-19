<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2c-5ubrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r2c-5ubrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:logo-osi" {...props}></Icon>
