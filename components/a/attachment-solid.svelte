<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8xd7l3mw.css';
import '../../css/e/emm9ff-2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q8xd7l3mw"/><path clip-rule="evenodd" class="emm9ff-2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:attachment-solid" {...props}></Icon>
