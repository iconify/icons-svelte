<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w65lbnl5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w65lbnl5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:playlist3" {...props}></Icon>
