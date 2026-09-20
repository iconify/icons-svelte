<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0l5f0mlr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0l5f0mlr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:caret-right-light" {...props}></Icon>
