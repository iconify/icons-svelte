<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmgy5nbjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmgy5nbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:github-alt" {...props}></Icon>
