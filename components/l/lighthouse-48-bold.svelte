<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rquh9bckn.css';
import '../../css/z/zembkqbot.css';
import '../../css/o/ok1e7zbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rquh9bckn"/><path class="zembkqbot"/><path class="ok1e7zbnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lighthouse-48-bold" {...props}></Icon>
