<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx7x4ac0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nx7x4ac0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:receive-square-filled" {...props}></Icon>
