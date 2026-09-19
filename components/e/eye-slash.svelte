<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el9pnwe6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="el9pnwe6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:eye-slash" {...props}></Icon>
