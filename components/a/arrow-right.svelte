<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk_o3uory.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mk_o3uory"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-right" {...props}></Icon>
