<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwcsq9-ee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="iwcsq9-ee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-number-1" {...props}></Icon>
