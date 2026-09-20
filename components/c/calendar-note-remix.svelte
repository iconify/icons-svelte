<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6v9hcbnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b6v9hcbnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:calendar-note-remix" {...props}></Icon>
