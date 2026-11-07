<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yybu3hn3z.css';
import '../../css/o/oa733acec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yybu3hn3z"/><path class="oa733acec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-right-to-line-outline" {...props}></Icon>
