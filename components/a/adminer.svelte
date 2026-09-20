<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq0eadb-w.css';
import '../../css/p/pav98pbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qq0eadb-w"/><path class="pav98pbev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adminer" {...props}></Icon>
