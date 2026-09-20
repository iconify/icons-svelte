<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-bldqb1w.css';
import '../../css/m/m7lzhdc8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-bldqb1w"/><path class="m7lzhdc8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:arrow-down-left" {...props}></Icon>
