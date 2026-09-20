<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnuh6xh8p.css';
import '../../css/n/nolroo2wn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vnuh6xh8p"/><path clip-rule="evenodd" class="nolroo2wn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:jpg-solid" {...props}></Icon>
