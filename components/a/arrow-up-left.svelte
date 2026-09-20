<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xendcgwaw.css';
import '../../css/x/xg4x14bqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xendcgwaw"/><path class="xg4x14bqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:arrow-up-left" {...props}></Icon>
