<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk858jx6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hk858jx6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:objects-column" {...props}></Icon>
