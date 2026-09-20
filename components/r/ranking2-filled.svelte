<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou39azb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ou39azb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ranking2-filled" {...props}></Icon>
