<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpslvk5st.css';
import '../../css/u/umkdqbblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qpslvk5st"/><path class="umkdqbblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:box-cutter-48-bold" {...props}></Icon>
