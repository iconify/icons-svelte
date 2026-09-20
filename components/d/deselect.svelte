<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsak1b5cw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zsak1b5cw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:deselect" {...props}></Icon>
