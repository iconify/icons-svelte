<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrhr6tbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrhr6tbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:hiking-stick" {...props}></Icon>
