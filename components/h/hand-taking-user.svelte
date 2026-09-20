<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c309e1k6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c309e1k6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:hand-taking-user" {...props}></Icon>
