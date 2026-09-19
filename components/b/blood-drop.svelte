<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pev-oobec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pev-oobec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blood-drop" {...props}></Icon>
