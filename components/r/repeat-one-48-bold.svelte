<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc4ommb6u.css';
import '../../css/i/it-ce4kqj.css';
import '../../css/r/rawgbsbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oc4ommb6u"/><path class="it-ce4kqj"/><path class="rawgbsbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:repeat-one-48-bold" {...props}></Icon>
