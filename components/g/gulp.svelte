<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh_-ponte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kh_-ponte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:gulp" {...props}></Icon>
