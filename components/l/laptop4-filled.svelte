<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx1e8bcvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nx1e8bcvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:laptop4-filled" {...props}></Icon>
