<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctxfvynty.css';
import '../../css/o/oyow42bcu.css';
import '../../css/q/q4qbprqxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ctxfvynty"/><path class="oyow42bcu"/><path class="q4qbprqxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flood-defence-48-bold" {...props}></Icon>
