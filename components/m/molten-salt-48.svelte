<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie-wxdblp.css';
import '../../css/x/xl5sv-boc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ie-wxdblp"/><path class="xl5sv-boc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:molten-salt-48" {...props}></Icon>
