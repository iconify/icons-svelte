<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_p-l7xft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v_p-l7xft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dagster-dark" {...props}></Icon>
