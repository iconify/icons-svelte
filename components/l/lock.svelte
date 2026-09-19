<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5lpkiu3h.css';
import '../../css/e/euvix8w7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5lpkiu3h"/><path class="euvix8w7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:lock" {...props}></Icon>
