<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aokn9xt1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aokn9xt1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:eqb" {...props}></Icon>
