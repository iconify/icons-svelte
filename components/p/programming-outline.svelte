<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/augjxln2c.css';
import '../../css/c/c1ebsvb3l.css';
import '../../css/n/nbozb93jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="augjxln2c"/><path class="c1ebsvb3l"/><path clip-rule="evenodd" class="nbozb93jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:programming-outline" {...props}></Icon>
