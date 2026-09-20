<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in9d5ac6n.css';
import '../../css/n/n3rld-six.css';
import '../../css/a/ani7f3b7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="in9d5ac6n"><path class="n3rld-six"/><path class="ani7f3b7w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:align-right" {...props}></Icon>
