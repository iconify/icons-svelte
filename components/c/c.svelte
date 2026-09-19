<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0gz3gb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="z0gz3gb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:c" {...props}></Icon>
