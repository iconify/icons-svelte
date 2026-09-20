<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t05e9cc4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t05e9cc4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:365datascience" {...props}></Icon>
