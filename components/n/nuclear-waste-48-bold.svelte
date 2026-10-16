<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-lmpi58f.css';
import '../../css/u/uqtphxb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q-lmpi58f"/><path class="uqtphxb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:nuclear-waste-48-bold" {...props}></Icon>
