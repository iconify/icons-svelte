<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlo2jcqcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mlo2jcqcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:flask-filled" {...props}></Icon>
