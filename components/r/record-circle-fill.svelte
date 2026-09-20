<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drlddqb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drlddqb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:record-circle-fill" {...props}></Icon>
