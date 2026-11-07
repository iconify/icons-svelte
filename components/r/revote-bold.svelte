<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddmmyzkas.css';
import '../../css/l/lz0rx605g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ddmmyzkas"/><path class="lz0rx605g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:revote-bold" {...props}></Icon>
