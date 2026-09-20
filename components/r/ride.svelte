<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5_92ry4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f5_92ry4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ride" {...props}></Icon>
