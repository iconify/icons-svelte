<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt74trb9i.css';
import '../../css/f/fz-5llb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rt74trb9i"/><path class="fz-5llb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:comment-block-solid" {...props}></Icon>
