<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usm6v_bue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="usm6v_bue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:angle-up-square-filled" {...props}></Icon>
