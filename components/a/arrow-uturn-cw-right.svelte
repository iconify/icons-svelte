<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5ddmwcld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v5ddmwcld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-uturn-cw-right" {...props}></Icon>
