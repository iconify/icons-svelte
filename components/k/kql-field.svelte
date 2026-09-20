<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdcoovbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":10};
const content = `<path class="tdcoovbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:kql-field" {...props}></Icon>
