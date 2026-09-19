<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymy8u3fmy.css';
import '../../css/d/di3cg09op.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymy8u3fmy"/><path class="di3cg09op"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:analyze-filled" {...props}></Icon>
