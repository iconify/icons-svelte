<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjl44flrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjl44flrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:copy-light" {...props}></Icon>
