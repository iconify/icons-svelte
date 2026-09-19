<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6ad_v4zt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6ad_v4zt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ikea-haddebo" {...props}></Icon>
