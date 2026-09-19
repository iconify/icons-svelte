<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cos4ynbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cos4ynbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:romain-letttace" {...props}></Icon>
