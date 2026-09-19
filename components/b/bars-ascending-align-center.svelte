<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou84d-bcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ou84d-bcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:bars-ascending-align-center" {...props}></Icon>
