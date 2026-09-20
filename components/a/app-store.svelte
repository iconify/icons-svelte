<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cni5d5ngx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cni5d5ngx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:app-store" {...props}></Icon>
