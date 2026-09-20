<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6ibs_b5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6ibs_b5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gitea" {...props}></Icon>
