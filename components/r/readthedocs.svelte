<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9ppn5bmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9ppn5bmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:readthedocs" {...props}></Icon>
