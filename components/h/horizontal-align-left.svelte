<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4z5ngy-x.css';
import '../../css/x/xqiru0m4e.css';
import '../../css/b/blbmi0irt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4z5ngy-x"/><path class="xqiru0m4e"/><path class="blbmi0irt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:horizontal-align-left" {...props}></Icon>
