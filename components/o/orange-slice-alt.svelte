<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugv8qvw0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugv8qvw0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:orange-slice-alt" {...props}></Icon>
