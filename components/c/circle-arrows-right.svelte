<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyw5h7vrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vyw5h7vrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:circle-arrows-right" {...props}></Icon>
