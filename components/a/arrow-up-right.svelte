<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhq9u8zqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nhq9u8zqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-up-right" {...props}></Icon>
