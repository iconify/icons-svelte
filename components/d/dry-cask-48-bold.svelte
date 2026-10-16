<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ownw2kb0e.css';
import '../../css/t/t1dfkwo5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ownw2kb0e"/><path class="t1dfkwo5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dry-cask-48-bold" {...props}></Icon>
