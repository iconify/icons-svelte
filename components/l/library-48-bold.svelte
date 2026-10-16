<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6cvwtbsp.css';
import '../../css/m/mi7mcubng.css';
import '../../css/w/wu28wrb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d6cvwtbsp"/><path class="mi7mcubng"/><path class="wu28wrb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:library-48-bold" {...props}></Icon>
