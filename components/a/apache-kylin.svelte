<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho6lhrbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ho6lhrbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:apache-kylin" {...props}></Icon>
