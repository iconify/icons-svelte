<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgjfhxb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cgjfhxb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pager-solid" {...props}></Icon>
