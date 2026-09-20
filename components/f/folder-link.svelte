<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie91gw6sh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ie91gw6sh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:folder-link" {...props}></Icon>
