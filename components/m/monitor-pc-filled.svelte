<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aap0qvl0c.css';
import '../../css/i/ia275-bew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aap0qvl0c"/><path class="ia275-bew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:monitor-pc-filled" {...props}></Icon>
