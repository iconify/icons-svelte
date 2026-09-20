<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/boh9b_bqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="boh9b_bqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:info-fill" {...props}></Icon>
