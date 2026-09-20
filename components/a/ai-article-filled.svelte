<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilg756wim.css';
import '../../css/l/llov8mbku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilg756wim"/><path class="llov8mbku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:ai-article-filled" {...props}></Icon>
