<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md1gexvna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="md1gexvna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:flask-fill" {...props}></Icon>
